<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm2232bcw.css';
import '../../css/e/ev2u2w4wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm2232bcw"/><path class="ev2u2w4wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:miele" /></template>
