<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs1so-b4l.css';
import '../../css/w/wobm3acef.css';
import '../../css/x/x5lbktbtf.css';
import '../../css/h/hzem-r0io.css';
import '../../css/v/vjbvj13aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bs1so-b4l"/><circle class="wobm3acef"/><circle class="x5lbktbtf"/><circle class="hzem-r0io"/><path class="vjbvj13aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:prompt-template" /></template>
