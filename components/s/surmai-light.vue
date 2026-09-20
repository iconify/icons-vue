<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh6cjl76d.css';
import '../../css/f/fpmgnqbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jh6cjl76d"/><path class="fpmgnqbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surmai-light" /></template>
