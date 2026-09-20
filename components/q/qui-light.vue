<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-7vtqbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-7vtqbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qui-light" /></template>
