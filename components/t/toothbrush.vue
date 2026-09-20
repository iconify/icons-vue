<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iormuebre.css';
import '../../css/f/fzppklb-k.css';
import '../../css/p/p0rwbubiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="iormuebre"/><path class="fzppklb-k"/><path class="p0rwbubiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:toothbrush" /></template>
