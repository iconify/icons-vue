<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf376njnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gf376njnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nzb-dav-dark" /></template>
