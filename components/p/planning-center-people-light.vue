<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it2cgzg4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="it2cgzg4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-people-light" /></template>
