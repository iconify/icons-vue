<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds4hig52e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds4hig52e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rancher" /></template>
