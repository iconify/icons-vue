<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/islpwrbax.css';
import '../../css/f/fg_9inbkk.css';
import '../../css/g/g1vushbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="islpwrbax"/><path class="fg_9inbkk"/><path class="g1vushbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mushroom" /></template>
