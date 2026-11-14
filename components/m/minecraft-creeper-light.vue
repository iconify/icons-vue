<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3y5qibll.css';
import '../../css/b/bxrcbrb3m.css';
import '../../css/r/r-qi2rbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3y5qibll"/><path class="bxrcbrb3m"/><path class="r-qi2rbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minecraft-creeper-light" /></template>
