<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-fh7-g-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-fh7-g-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-de-tc" /></template>
