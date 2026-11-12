<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3o88hbsh.css';
import '../../css/n/ny54whb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3o88hbsh"/><path class="ny54whb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tldraw" /></template>
