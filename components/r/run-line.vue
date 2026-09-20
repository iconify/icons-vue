<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyf_p3b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyf_p3b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:run-line" /></template>
