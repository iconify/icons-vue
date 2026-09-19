<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x63la694e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x63la694e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nix" /></template>
