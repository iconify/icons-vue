<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu29sma9m.css';
import '../../css/y/y8de8nbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lu29sma9m"/><path class="y8de8nbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:share-2-20" /></template>
