<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th6xvpbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="th6xvpbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nested-hearts" /></template>
