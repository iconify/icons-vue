<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch-5d0oph.css';
import '../../css/n/ndg-4phim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ch-5d0oph"/><path class="ndg-4phim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reaparr-light" /></template>
