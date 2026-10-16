<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jithrbamh.css';
import '../../css/a/abeu7fb-k.css';
import '../../css/a/a40uxxbuo.css';
import '../../css/d/dyg3u9bac.css';
import '../../css/c/cz9a8mbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jithrbamh"/><path class="abeu7fb-k"/><path class="a40uxxbuo"/><path class="dyg3u9bac"/><path class="cz9a8mbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:neural-network-20" /></template>
