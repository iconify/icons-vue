<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnb11-bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jnb11-bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:roadsignleft" /></template>
