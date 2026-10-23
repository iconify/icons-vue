<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9-occkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9-occkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:video-off" /></template>
