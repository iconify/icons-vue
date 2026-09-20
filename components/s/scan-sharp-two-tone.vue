<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctljy3bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctljy3bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-sharp-two-tone" /></template>
