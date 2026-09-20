<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qitrk6b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qitrk6b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:male-line" /></template>
