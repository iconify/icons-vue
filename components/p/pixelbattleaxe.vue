<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fym710b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fym710b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelbattleaxe" /></template>
