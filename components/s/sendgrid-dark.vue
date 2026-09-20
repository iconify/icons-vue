<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhc-wtc2y.css';
import '../../css/p/phf4gf3fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhc-wtc2y"/><path class="phf4gf3fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sendgrid-dark" /></template>
