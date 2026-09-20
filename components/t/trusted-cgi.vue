<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7wy-vb7x.css';
import '../../css/x/xnp4gerbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i7wy-vb7x"/><path class="xnp4gerbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trusted-cgi" /></template>
