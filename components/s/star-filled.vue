<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkb5fmb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gkb5fmb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:star-filled" /></template>
