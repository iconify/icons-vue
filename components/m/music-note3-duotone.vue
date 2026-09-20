<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6l8xqbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6l8xqbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note3-duotone" /></template>
