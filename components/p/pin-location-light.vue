<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqlbbubhn.css';
import '../../css/n/ngbp4qb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqlbbubhn"/><path class="ngbp4qb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pin-location-light" /></template>
