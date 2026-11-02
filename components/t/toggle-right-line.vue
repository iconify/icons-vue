<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm7r9eb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm7r9eb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-right-line" /></template>
