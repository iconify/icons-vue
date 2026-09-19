<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2_1icpng.css';
import '../../css/x/xi4z0dojk.css';
import '../../css/h/hltazq3ru.css';
import '../../css/o/o_a2bsbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2_1icpng"/><path class="xi4z0dojk"/><path class="hltazq3ru"/><path class="o_a2bsbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:vertical-align-bottom1" /></template>
