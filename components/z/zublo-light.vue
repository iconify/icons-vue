<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndgwe3cri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ndgwe3cri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zublo-light" /></template>
