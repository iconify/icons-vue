<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nubaqiiux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nubaqiiux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rotate-right2-filled" /></template>
