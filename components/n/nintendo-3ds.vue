<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbcfpcb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fbcfpcb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nintendo-3ds" /></template>
