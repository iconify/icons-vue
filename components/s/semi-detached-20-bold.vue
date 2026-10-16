<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdcnnnb3n.css';
import '../../css/x/xxc3j4pon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gdcnnnb3n"/><path class="xxc3j4pon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:semi-detached-20-bold" /></template>
