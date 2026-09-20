<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k47x0ekmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k47x0ekmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tesla" /></template>
