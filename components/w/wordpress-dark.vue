<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9ih55fgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9ih55fgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wordpress-dark" /></template>
