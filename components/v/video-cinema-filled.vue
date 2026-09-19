<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhv2lljao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhv2lljao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:video-cinema-filled" /></template>
