<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkvb5p1nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkvb5p1nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mini-qr-dark" /></template>
