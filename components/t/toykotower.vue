<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qetnckbkp.css';
import '../../css/k/kgks08b4h.css';
import '../../css/u/ubw9i8bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qetnckbkp"/><path class="kgks08b4h"/><path class="ubw9i8bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:toykotower" /></template>
