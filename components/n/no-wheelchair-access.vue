<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lji5nfbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lji5nfbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-wheelchair-access" /></template>
