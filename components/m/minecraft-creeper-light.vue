<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-s51kssr.css';
import '../../css/j/j74io277e.css';
import '../../css/s/sdjrrqbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-s51kssr"/><path class="j74io277e"/><path class="sdjrrqbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:minecraft-creeper-light" /></template>
