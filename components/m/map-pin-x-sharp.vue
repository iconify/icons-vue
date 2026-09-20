<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0l9u9b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0l9u9b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-x-sharp" /></template>
