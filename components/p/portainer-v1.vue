<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co3ape_oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co3ape_oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portainer-v1" /></template>
