<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3c725ova.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x3c725ova"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle-badge-exclam" /></template>
