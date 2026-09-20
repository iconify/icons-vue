<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw4zcdvad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rw4zcdvad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapdrop-light" /></template>
