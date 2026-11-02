<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qci7j6b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qci7j6b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:section-line" /></template>
