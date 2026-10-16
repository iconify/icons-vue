<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gza0lnxru.css';
import '../../css/e/e6mnr5buq.css';
import '../../css/j/jcyd-oqqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gza0lnxru"/><path class="e6mnr5buq"/><path class="jcyd-oqqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:xor-gate-20" /></template>
