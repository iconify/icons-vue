<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0y0c0b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="t0y0c0b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:message-f" /></template>
