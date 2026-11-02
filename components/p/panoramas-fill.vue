<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2g5psuob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2g5psuob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:panoramas-fill" /></template>
