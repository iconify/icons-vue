<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aomy0cbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aomy0cbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:video-camera-16-solid" /></template>
