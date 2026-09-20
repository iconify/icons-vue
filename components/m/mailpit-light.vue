<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n30rbnbif.css';
import '../../css/g/g13wum06j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n30rbnbif"/><path class="g13wum06j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailpit-light" /></template>
