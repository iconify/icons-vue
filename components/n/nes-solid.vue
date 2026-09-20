<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m45x_vbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m45x_vbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:nes-solid" /></template>
