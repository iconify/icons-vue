<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyngyrbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kyngyrbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:project-history" /></template>
