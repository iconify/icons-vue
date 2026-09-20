<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edizufb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edizufb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:trash-active" /></template>
