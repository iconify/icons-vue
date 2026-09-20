<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_es2wzdn.css';
import '../../css/j/jbm7ubcxn.css';
import '../../css/b/b-waoerrw.css';
import '../../css/c/ck6sdqbkp.css';
import '../../css/n/n44qfl4eh.css';
import '../../css/s/se506vbgv.css';
import '../../css/n/n93g78bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k_es2wzdn"/><path class="jbm7ubcxn"/><circle class="b-waoerrw"/><path class="ck6sdqbkp"/><path class="n44qfl4eh"/><circle class="se506vbgv"/><path class="n93g78bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:panda" /></template>
