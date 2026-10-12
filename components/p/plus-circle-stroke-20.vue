<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xukl73g2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xukl73g2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-circle-stroke-20" /></template>
