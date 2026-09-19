<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo82rec2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xo82rec2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:musescore" /></template>
