<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0n2qbbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n0n2qbbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:swarm" /></template>
