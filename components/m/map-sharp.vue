<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmy4j9b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmy4j9b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-sharp" /></template>
