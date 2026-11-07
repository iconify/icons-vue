<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahsrkib1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahsrkib1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:relaytv-dark" /></template>
