<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc2t_gb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lc2t_gb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planarally-dark" /></template>
