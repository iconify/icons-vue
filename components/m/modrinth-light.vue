<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgnz_7dgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgnz_7dgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:modrinth-light" /></template>
