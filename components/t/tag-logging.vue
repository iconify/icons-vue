<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2npi2bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u2npi2bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tag-logging" /></template>
