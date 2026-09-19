<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o755flidq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o755flidq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sign" /></template>
