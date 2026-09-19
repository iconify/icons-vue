<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqa9ondhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqa9ondhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vr-headset-filled" /></template>
