<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9i1vdbko.css';
import '../../css/o/oakyvybig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f9i1vdbko"/><path class="oakyvybig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-erased" /></template>
