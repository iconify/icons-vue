<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3o88hbsh.css';
import '../../css/q/q5chu0b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v3o88hbsh"/><path class="q5chu0b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tldraw" /></template>
