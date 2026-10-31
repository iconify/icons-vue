<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb9b0qbvi.css';
import '../../css/v/vv-rc2b1z.css';
import '../../css/d/desiwpbvm.css';
import '../../css/r/r130d-bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="mb9b0qbvi"/><path class="vv-rc2b1z"/><path class="desiwpbvm"/><path class="r130d-bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:mauritius" /></template>
