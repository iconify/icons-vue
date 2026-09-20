<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0ix46b3r.css';
import '../../css/p/p1yx4trbb.css';
import '../../css/d/dcy5gh-xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="r0ix46b3r"/><circle class="p1yx4trbb"/><path class="dcy5gh-xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:navidrome" /></template>
