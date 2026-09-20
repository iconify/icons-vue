<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt6iyeqqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt6iyeqqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rectangle-line" /></template>
