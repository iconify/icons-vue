<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br0ven8-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="br0ven8-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:postage-stamp-light" /></template>
