<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-08wh0_j.css';
import '../../css/v/vnuucwq6l.css';
import '../../css/s/s7cf2jbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-08wh0_j"/><path class="vnuucwq6l"/><path class="s7cf2jbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mongodb" /></template>
