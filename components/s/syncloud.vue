<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_ieiz18n.css';
import '../../css/d/d5xclqbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_ieiz18n"/><path class="d5xclqbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:syncloud" /></template>
