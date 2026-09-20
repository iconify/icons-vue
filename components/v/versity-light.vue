<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo5au9b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uo5au9b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:versity-light" /></template>
