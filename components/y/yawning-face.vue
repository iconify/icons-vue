<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jnd9-ne4y.css';
import '../../css/m/mh6j-jb0n.css';
import '../../css/z/zvzu5zjds.css';
import '../../css/g/g-cvnihgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jnd9-ne4y"/><circle class="mh6j-jb0n"/><path clip-rule="evenodd" class="zvzu5zjds"/><path clip-rule="evenodd" class="g-cvnihgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:yawning-face" /></template>
