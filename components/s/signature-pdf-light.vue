<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emtqbdbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="emtqbdbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:signature-pdf-light" /></template>
