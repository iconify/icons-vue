<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s481l7_yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s481l7_yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-gear" /></template>
