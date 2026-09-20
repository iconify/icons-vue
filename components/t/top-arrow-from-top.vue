<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb_xysb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb_xysb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:top-arrow-from-top" /></template>
