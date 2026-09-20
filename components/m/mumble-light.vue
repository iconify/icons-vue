<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y91xbsbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y91xbsbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mumble-light" /></template>
