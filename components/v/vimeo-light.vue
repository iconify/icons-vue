<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twipirh2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="twipirh2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vimeo-light" /></template>
