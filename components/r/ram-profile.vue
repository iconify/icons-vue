<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oenq7gbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oenq7gbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ram-profile" /></template>
