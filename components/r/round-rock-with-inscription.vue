<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6weuyb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t6weuyb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:round-rock-with-inscription" /></template>
