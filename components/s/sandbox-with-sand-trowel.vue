<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_k0u_bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h_k0u_bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sandbox-with-sand-trowel" /></template>
