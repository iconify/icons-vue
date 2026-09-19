<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg8rqbcrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg8rqbcrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scene-read" /></template>
