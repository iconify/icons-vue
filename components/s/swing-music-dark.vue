<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f08a3zbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f08a3zbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swing-music-dark" /></template>
