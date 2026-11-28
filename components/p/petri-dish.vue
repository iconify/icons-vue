<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9_hp6odt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9_hp6odt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:petri-dish" /></template>
