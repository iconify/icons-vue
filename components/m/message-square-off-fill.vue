<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dna4t1d0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dna4t1d0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-off-fill" /></template>
