<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7k0-5d4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n7k0-5d4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:snes-solid" /></template>
