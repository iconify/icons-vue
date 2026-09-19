<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9s5racgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9s5racgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-hammer" /></template>
