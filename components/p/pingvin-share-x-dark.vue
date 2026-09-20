<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td9bw8nuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="td9bw8nuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pingvin-share-x-dark" /></template>
