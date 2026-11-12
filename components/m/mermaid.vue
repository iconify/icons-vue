<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu7p034nk.css';
import '../../css/e/evg8hlkme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nu7p034nk"/><path class="evg8hlkme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mermaid" /></template>
