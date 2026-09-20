<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5v3zqbul.css';
import '../../css/q/qv0ny4dca.css';
import '../../css/p/pjqkbnbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5v3zqbul"/><path class="qv0ny4dca"/><path class="pjqkbnbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:window-maximize" /></template>
