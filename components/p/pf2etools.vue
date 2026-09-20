<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksigsecyg.css';
import '../../css/s/si0nt0a3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksigsecyg"/><path class="si0nt0a3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pf2etools" /></template>
