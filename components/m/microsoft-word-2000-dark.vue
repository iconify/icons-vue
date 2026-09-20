<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsp4kg7um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bsp4kg7um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2000-dark" /></template>
