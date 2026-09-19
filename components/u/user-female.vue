<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb16_1llh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb16_1llh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:user-female" /></template>
