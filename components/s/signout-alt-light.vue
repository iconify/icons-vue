<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn3-hqbra.css';
import '../../css/r/r-lddkblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn3-hqbra"/><path class="r-lddkblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signout-alt-light" /></template>
