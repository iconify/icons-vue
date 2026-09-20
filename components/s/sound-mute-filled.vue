<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uffnlp-lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uffnlp-lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sound-mute-filled" /></template>
