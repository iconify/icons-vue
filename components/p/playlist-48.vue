<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd9chqbvs.css';
import '../../css/j/jz9dkbbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sd9chqbvs"/><path class="jz9dkbbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:playlist-48" /></template>
