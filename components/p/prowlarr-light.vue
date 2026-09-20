<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v74j5acgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v74j5acgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prowlarr-light" /></template>
