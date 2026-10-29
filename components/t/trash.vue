<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxkycjbej.css';
import '../../css/f/fff81-bmi.css';
import '../../css/f/flstcrbhi.css';
import '../../css/o/o71e8i_kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxkycjbej wm-a"/><path class="fff81-bmi wm-k"/><path class="flstcrbhi wm-k"/><path class="o71e8i_kg wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:trash" /></template>
