<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x39p64gnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x39p64gnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vanguard-light" /></template>
