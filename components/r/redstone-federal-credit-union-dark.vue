<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0rob0b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n0rob0b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redstone-federal-credit-union-dark" /></template>
