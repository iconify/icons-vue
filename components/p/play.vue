<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjljb6bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjljb6bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:play" /></template>
