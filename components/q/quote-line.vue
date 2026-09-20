<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvt-im0fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvt-im0fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:quote-line" /></template>
