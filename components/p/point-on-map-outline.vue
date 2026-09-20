<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaz9sl6in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oaz9sl6in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-outline" /></template>
