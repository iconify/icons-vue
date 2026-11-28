<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-ep_-cqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-ep_-cqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:speaker" /></template>
