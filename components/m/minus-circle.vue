<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn0ft0bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn0ft0bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:minus-circle" /></template>
