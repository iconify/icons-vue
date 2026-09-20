<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/danrfbc9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="danrfbc9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tyre-line" /></template>
