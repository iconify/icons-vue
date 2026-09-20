<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ep0bbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="n_ep0bbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:sheild" /></template>
