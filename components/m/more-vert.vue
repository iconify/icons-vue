<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz7kfkb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":88,"height":384};
const content = `<path class="pz7kfkb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:more-vert" /></template>
