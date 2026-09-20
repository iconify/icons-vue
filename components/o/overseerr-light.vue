<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar1p11b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ar1p11b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:overseerr-light" /></template>
