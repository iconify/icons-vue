<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp6z-4mxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp6z-4mxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:megaphone-2-fill" /></template>
