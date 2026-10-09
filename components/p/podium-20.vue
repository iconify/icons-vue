<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnazeqbdf.css';
import '../../css/v/vihqj-brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lnazeqbdf"/><path class="vihqj-brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:podium-20" /></template>
