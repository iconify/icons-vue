<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p67p4-ffp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p67p4-ffp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netalertx-dark" /></template>
