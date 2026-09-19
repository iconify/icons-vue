<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz6lpmbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pz6lpmbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-unfollow-stroke-12" /></template>
