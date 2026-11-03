<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynsy5g-wh.css';
import '../../css/w/wjoeyx4qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ynsy5g-wh"/><path class="wjoeyx4qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:multi-scrobbler" /></template>
