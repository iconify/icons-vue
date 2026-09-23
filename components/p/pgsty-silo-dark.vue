<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2k-n7s4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2k-n7s4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pgsty-silo-dark" /></template>
