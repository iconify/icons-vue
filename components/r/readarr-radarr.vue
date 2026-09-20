<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-wkamaxf.css';
import '../../css/d/dmusveb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="dmusveb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:readarr-radarr" /></template>
