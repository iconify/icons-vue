<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chp_nybzg.css';
import '../../css/z/ze1bd391g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="chp_nybzg"/><path class="ze1bd391g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:zsh" /></template>
