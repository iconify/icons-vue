<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl3z94bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl3z94bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:script-2" /></template>
