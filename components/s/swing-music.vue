<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6hwvs4-a.css';
import '../../css/h/heccpqbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6hwvs4-a"/><path class="heccpqbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swing-music" /></template>
