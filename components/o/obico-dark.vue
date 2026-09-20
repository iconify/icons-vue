<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b62ajwbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b62ajwbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:obico-dark" /></template>
