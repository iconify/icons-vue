<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9prg-o0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":528};
const content = `<path class="v9prg-o0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pin-map" /></template>
