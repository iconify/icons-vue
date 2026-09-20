<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft2odlb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ft2odlb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-bars-weak-signal" /></template>
