<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_mglgxaq.css';
import '../../css/p/p-_y-_-ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_mglgxaq"/><path class="p-_y-_-ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netgear" /></template>
