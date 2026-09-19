<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz2k0mbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sz2k0mbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:potion-of-madness" /></template>
