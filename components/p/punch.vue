<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxz13rg8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lxz13rg8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:punch" /></template>
