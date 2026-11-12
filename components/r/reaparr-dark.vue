<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r22q9yb_l.css';
import '../../css/f/fjrtewbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r22q9yb_l"/><path class="fjrtewbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reaparr-dark" /></template>
