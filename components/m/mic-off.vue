<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkmqn04ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkmqn04ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mic-off" /></template>
