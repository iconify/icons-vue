<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_e4sjb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_e4sjb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr-4k-light" /></template>
