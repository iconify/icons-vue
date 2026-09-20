<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb_gupbgs.css';
import '../../css/i/iquxmufry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jb_gupbgs"/><path class="iquxmufry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:new-releases" /></template>
