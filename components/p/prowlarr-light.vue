<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b25a24pbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b25a24pbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prowlarr-light" /></template>
