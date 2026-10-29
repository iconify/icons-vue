<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ercj48bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ercj48bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:navigation-2" /></template>
