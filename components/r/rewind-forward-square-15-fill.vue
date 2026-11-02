<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueaz-086o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueaz-086o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-square-15-fill" /></template>
