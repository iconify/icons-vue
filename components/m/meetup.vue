<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgok3r4hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rgok3r4hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:meetup" /></template>
