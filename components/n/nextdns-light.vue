<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s25wggbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s25wggbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextdns-light" /></template>
