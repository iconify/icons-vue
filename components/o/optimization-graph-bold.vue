<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts8762bta.css';
import '../../css/a/au3jsqbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts8762bta"/><path class="au3jsqbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:optimization-graph-bold" /></template>
