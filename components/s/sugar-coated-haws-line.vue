<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gelac1c3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gelac1c3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sugar-coated-haws-line" /></template>
