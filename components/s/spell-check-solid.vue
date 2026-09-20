<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mib7gib8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mib7gib8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:spell-check-solid" /></template>
