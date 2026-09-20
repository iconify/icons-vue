<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5a8_trli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5a8_trli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:modrinth" /></template>
