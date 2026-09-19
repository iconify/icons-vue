<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyv22vb3x.css';
import '../../css/i/i7sr6ubzr.css';
import '../../css/s/s64_1ebkq.css';
import '../../css/g/gg7u_jkqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyv22vb3x"/><path class="i7sr6ubzr"/><path class="s64_1ebkq"/><path class="gg7u_jkqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:speech-to-text" /></template>
