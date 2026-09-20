<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k32cw6e7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k32cw6e7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:trolleybus" /></template>
