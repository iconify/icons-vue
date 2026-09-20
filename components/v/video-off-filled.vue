<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltqe21uvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltqe21uvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-off-filled" /></template>
