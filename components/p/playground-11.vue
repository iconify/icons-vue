<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyeiszbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="uyeiszbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:playground-11" /></template>
