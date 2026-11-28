<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twu26sb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twu26sb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:window-awning-solid" /></template>
