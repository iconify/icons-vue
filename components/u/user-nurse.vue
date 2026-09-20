<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csd2fybuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csd2fybuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:user-nurse" /></template>
