<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdvnstoeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdvnstoeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:origin-logo-bold" /></template>
