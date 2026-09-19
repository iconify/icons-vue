<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzfb64bla.css';
import '../../css/k/kbh20vd3x.css';
import '../../css/m/mexzrqjpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fzfb64bla"/><path class="kbh20vd3x"/><path class="mexzrqjpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:redhat" /></template>
