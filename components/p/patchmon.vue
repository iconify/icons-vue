<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvpxr2b8r.css';
import '../../css/u/u13r1zb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yvpxr2b8r"/><path class="u13r1zb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:patchmon" /></template>
