<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foe4c7nyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="foe4c7nyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tree-two-level" /></template>
