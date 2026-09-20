<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbq5kebal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbq5kebal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rotate-to-vertical-fill" /></template>
