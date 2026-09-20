<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6br75yqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h6br75yqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pve-ups-dark" /></template>
