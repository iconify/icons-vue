<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h20o-8bsr.css';
import '../../css/m/mb7553tox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="h20o-8bsr"/><path class="mb7553tox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-foursquare" /></template>
