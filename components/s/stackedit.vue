<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz33170rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz33170rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stackedit" /></template>
