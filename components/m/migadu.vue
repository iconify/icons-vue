<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr17dabrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr17dabrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:migadu" /></template>
