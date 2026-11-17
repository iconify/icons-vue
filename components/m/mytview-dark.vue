<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4wa7qbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h4wa7qbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mytview-dark" /></template>
