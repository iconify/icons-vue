<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il_zhnbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il_zhnbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:upload-1" /></template>
