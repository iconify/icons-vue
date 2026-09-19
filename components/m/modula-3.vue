<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkcl6dbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkcl6dbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:modula-3" /></template>
