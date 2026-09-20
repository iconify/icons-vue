<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n73j_hptb.css';
import '../../css/p/pkgwtlppi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n73j_hptb"/><path class="pkgwtlppi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-velocity" /></template>
