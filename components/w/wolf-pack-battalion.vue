<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5re3sbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5re3sbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:wolf-pack-battalion" /></template>
