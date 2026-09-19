<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv1kbccre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="pv1kbccre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-walking" /></template>
