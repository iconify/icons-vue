<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc0ucyjua.css';
import '../../css/c/c-ehkdbnh.css';
import '../../css/l/llb7ncbpf.css';
import '../../css/q/q0xn5iwfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mc0ucyjua"/><path class="c-ehkdbnh"/><path class="llb7ncbpf"/><path class="q0xn5iwfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:subversion-wordmark" /></template>
