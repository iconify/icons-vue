<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp40olbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hp40olbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:token" /></template>
