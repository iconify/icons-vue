<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an_myyb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="an_myyb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netlify-dark" /></template>
