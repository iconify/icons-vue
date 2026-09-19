<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zstbz94ff.css';
import '../../css/t/t4b6zqbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="zstbz94ff"/><path class="t4b6zqbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-circle-stroke-12" /></template>
