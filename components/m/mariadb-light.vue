<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frn3nhblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="frn3nhblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mariadb-light" /></template>
