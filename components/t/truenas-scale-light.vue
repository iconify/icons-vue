<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-m8bqbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-m8bqbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:truenas-scale-light" /></template>
