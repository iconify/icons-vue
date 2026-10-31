<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvwtb5uoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvwtb5uoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:vr-headset-gloss" /></template>
