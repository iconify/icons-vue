<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_jprcc5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_jprcc5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:star-o" /></template>
