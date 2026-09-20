<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/suuz8d7iq.css';
import '../../css/b/bauxs7clz.css';
import '../../css/o/oogehbcah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="suuz8d7iq"/><path class="bauxs7clz"/><path class="oogehbcah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pin-alt-duotone-line" /></template>
