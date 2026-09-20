<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n204gnbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n204gnbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:puzzle-piece" /></template>
