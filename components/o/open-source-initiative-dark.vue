<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn9s_j5ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hn9s_j5ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-source-initiative-dark" /></template>
