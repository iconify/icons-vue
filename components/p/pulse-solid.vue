<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_xopgbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_xopgbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:pulse-solid" /></template>
