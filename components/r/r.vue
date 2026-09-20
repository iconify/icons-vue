<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btu8jzbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btu8jzbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:r" /></template>
