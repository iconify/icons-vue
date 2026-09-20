<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5z6um0tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t5z6um0tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plex-dash-light" /></template>
