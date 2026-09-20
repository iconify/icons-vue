<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbde64sxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbde64sxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:munin-dark" /></template>
