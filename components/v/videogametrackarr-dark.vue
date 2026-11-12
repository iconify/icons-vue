<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7b9j-hgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7b9j-hgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:videogametrackarr-dark" /></template>
