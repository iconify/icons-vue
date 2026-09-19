<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxvai9vpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="mxvai9vpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:meetup" /></template>
