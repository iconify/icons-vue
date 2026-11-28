<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhsf1lb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhsf1lb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rotate-cw" /></template>
