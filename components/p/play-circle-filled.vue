<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdu_b2b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdu_b2b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:play-circle-filled" /></template>
