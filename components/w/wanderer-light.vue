<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg96vqbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xg96vqbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wanderer-light" /></template>
