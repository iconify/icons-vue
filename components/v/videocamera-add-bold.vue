<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-qt_m0ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-qt_m0ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-add-bold" /></template>
