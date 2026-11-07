<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rszymacgm.css';
import '../../css/l/laen_wd4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rszymacgm"/><path class="laen_wd4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-top-down-outline" /></template>
