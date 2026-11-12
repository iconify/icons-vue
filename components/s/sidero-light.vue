<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j35tezb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j35tezb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sidero-light" /></template>
