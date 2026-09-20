<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkgseabid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qkgseabid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:pedestrian-crosswalk" /></template>
