<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4zyklb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4zyklb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:options-sharp" /></template>
