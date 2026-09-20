<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kauthwa8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kauthwa8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storygraph-dark" /></template>
