<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy3n3jbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy3n3jbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tool-solid" /></template>
