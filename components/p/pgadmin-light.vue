<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf6l_pbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mf6l_pbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pgadmin-light" /></template>
