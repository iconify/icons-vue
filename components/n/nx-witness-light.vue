<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkmbvobhi.css';
import '../../css/f/fusmf-b6m.css';
import '../../css/l/ln0ym_was.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkmbvobhi"/><path class="fusmf-b6m"/><path class="ln0ym_was"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nx-witness-light" /></template>
