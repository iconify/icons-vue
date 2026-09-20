<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjma1yhgw.css';
import '../../css/y/yi3jdwbhm.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/f/fb76p4b_a.css';
import '../../css/y/yx3j-pcbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="yjma1yhgw"/><path class="yi3jdwbhm"/><g class="jn8qy4bru"><circle class="fb76p4b_a"/><path class="yx3j-pcbw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:prohibited" /></template>
