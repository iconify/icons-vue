<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihkbpcb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihkbpcb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-rhomb-filled" /></template>
