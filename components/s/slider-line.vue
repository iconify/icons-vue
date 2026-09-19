<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skqj38hxr.css';
import '../../css/y/y3lt4nbkz.css';
import '../../css/a/aay3jcb6i.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 skqj38hxr"/><path class="clr-i-outline clr-i-outline-path-2 y3lt4nbkz"/><path class="aay3jcb6i clr-i-outline clr-i-outline-path-3"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:slider-line" /></template>
