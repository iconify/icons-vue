<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxqmevb6p.css';
import '../../css/p/pan7dlbeh.css';
import '../../css/s/sjj76ybgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="uxqmevb6p"/><path class="pan7dlbeh"/><path class="sjj76ybgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tubehaus" /></template>
