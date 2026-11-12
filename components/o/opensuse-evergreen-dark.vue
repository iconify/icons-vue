<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djf9zbitb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djf9zbitb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-evergreen-dark" /></template>
