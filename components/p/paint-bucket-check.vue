<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpa1o5b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpa1o5b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paint-bucket-check" /></template>
