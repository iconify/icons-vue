<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avfeqsbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avfeqsbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ruler-solid" /></template>
