<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5eqbcc6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5eqbcc6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:to-bottom-one" /></template>
