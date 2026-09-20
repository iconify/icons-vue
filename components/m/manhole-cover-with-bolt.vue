<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcnii5bpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wcnii5bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:manhole-cover-with-bolt" /></template>
