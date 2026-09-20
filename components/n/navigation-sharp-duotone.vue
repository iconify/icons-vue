<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v47hdr-ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v47hdr-ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-sharp-duotone" /></template>
