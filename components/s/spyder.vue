<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dutclc24h.css';
import '../../css/x/x5f34xbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dutclc24h"/><path class="x5f34xbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:spyder" /></template>
