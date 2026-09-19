<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwqxrzb-l.css';
import '../../css/s/s18h12q8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qwqxrzb-l"/><path class="s18h12q8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:traffic-event" /></template>
