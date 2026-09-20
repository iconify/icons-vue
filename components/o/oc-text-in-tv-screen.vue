<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvhwjybhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pvhwjybhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:oc-text-in-tv-screen" /></template>
