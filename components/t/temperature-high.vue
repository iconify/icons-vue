<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of7srkb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="of7srkb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:temperature-high" /></template>
