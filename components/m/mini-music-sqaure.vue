<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/ii3b9xbkx.css';
import '../../css/t/t8r6agbqp.css';
import '../../css/b/bn9scm_6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ii3b9xbkx"/><path class="t8r6agbqp"/><path class="bn9scm_6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mini-music-sqaure" /></template>
