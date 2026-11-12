<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8ly-hb2i.css';
import '../../css/f/f9y25p_8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8ly-hb2i"/><path class="f9y25p_8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subarr" /></template>
