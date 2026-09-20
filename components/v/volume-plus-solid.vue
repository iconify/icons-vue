<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzb7-dbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzb7-dbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-plus-solid" /></template>
