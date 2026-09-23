<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq5v0fbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gq5v0fbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pgsty-silo-light" /></template>
