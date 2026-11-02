<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1uww3jwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1uww3jwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vip-1-fill" /></template>
