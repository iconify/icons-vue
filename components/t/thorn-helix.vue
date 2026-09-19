<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypnblsbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ypnblsbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thorn-helix" /></template>
