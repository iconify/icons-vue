<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg1eho4bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg1eho4bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-grid-r" /></template>
