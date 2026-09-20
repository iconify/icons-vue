<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfrfmybyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfrfmybyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-heart" /></template>
