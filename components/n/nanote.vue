<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcqbabccs.css';
import '../../css/d/dgwj8cbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcqbabccs"/><path class="dgwj8cbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nanote" /></template>
