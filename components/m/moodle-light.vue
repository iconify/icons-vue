<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gby602bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gby602bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moodle-light" /></template>
