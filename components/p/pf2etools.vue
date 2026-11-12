<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksigsecyg.css';
import '../../css/y/y-4aifk4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ksigsecyg"/><path class="y-4aifk4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pf2etools" /></template>
