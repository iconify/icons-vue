<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm7kl-mmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tm7kl-mmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-takeoff" /></template>
