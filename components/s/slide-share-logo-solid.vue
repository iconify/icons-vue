<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdat6-bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdat6-bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:slide-share-logo-solid" /></template>
