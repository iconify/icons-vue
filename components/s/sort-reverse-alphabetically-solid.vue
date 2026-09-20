<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga54jte-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ga54jte-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-reverse-alphabetically-solid" /></template>
