<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfh9e8-4g.css';
import '../../css/a/aou0j_yla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfh9e8-4g"/><path class="aou0j_yla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notepad-plus-plus-dark" /></template>
