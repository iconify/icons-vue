<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/givycqbte.css';
import '../../css/q/qi9ru7mur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="givycqbte"/><path class="qi9ru7mur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-git-compare" /></template>
