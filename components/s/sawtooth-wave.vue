<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9knjwb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9knjwb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:sawtooth-wave" /></template>
