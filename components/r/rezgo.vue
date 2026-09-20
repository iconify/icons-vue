<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqbut3hmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqbut3hmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rezgo" /></template>
