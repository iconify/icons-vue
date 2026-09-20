<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2dlt5bbm.css';
import '../../css/b/bd2_kcbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2dlt5bbm"/><path class="bd2_kcbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metadata-remote" /></template>
