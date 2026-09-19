<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdhez3b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdhez3b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:menu-alt-05" /></template>
