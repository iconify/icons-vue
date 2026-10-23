<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t64ob-b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t64ob-b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:text-align-justify-center" /></template>
