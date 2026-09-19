<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al0zveb0a.css';
import '../../css/a/ayfs0cb5s.css';
import '../../css/j/jy90cd2id.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="al0zveb0a"/><path class="ayfs0cb5s"/><path class="jy90cd2id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:newmoonwithface" /></template>
