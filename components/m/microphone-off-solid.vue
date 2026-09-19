<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9ef2wbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9ef2wbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:microphone-off-solid" /></template>
