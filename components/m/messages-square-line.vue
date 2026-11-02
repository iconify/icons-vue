<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay2k2nmzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay2k2nmzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:messages-square-line" /></template>
