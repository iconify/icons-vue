<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfeui5blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lfeui5blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wanderer-dark" /></template>
