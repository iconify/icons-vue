<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm1ssabvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bm1ssabvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portainer-v1-light" /></template>
