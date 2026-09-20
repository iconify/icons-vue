<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thiy84bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thiy84bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:trending-down-solid" /></template>
