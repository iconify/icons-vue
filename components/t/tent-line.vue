<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjq44blgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjq44blgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tent-line" /></template>
