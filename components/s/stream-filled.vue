<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4018hsjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e4018hsjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stream-filled" /></template>
