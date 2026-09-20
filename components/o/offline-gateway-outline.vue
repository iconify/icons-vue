<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9gpwtbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9gpwtbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:offline-gateway-outline" /></template>
