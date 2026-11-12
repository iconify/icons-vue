<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7st-bkc.css';
import '../../css/e/e0tloob2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7st-bkc"/><path class="e0tloob2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tailscale" /></template>
