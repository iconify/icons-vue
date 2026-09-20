<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nupf9xppo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nupf9xppo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mind-map" /></template>
