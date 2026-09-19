<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn2rp_bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pn2rp_bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:meat" /></template>
