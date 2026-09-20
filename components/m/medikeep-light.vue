<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nix2b51po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nix2b51po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medikeep-light" /></template>
