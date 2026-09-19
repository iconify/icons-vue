<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-lopnnqb.css';
import '../../css/w/win9rhm6g.css';
import '../../css/n/nrkn4rbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="n-lopnnqb"/><path clip-rule="evenodd" class="win9rhm6g"/><path class="nrkn4rbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nixos-wordmark" /></template>
