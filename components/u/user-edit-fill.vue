<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egs3wlbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egs3wlbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-edit-fill" /></template>
