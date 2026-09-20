<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiklc0b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iiklc0b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:musicbrainz-picard-light" /></template>
