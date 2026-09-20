<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzndz51eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzndz51eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pencil-ai-24" /></template>
