<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk2e_09ob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uk2e_09ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sverd-i-fjell" /></template>
