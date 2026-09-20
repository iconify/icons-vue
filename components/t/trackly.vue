<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr7toqbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fr7toqbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trackly" /></template>
