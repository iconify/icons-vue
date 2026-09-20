<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awlel4dzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awlel4dzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-filled" /></template>
