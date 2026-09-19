<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw7s5sw9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mw7s5sw9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:x-stroke-12" /></template>
