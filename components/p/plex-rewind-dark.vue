<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkh-nabnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkh-nabnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plex-rewind-dark" /></template>
