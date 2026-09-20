<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd_s0sb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wd_s0sb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pepperminty-wiki-light" /></template>
