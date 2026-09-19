<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyzi_3zlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyzi_3zlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ollama" /></template>
