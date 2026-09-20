<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8924ub-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8924ub-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-tack" /></template>
