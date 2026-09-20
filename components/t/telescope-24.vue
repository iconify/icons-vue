<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpu57nboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpu57nboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:telescope-24" /></template>
