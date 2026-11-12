<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-5qssb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k-5qssb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pf2etools-light" /></template>
