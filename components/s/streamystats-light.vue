<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i86vmwb3r.css';
import '../../css/c/cogmg3blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i86vmwb3r"/><path class="cogmg3blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:streamystats-light" /></template>
