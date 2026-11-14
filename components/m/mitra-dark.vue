<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbk7monww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nbk7monww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mitra-dark" /></template>
