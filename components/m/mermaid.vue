<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu7p034nk.css';
import '../../css/b/b8kyosqzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nu7p034nk"/><path class="b8kyosqzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mermaid" /></template>
