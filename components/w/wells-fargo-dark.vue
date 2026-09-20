<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szpeyz0sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szpeyz0sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wells-fargo-dark" /></template>
