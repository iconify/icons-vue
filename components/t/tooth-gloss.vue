<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd679kpub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd679kpub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tooth-gloss" /></template>
