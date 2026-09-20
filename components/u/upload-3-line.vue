<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo8q8sbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo8q8sbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:upload-3-line" /></template>
