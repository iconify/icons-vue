<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuhezrb5q.css';
import '../../css/r/rjngqpptk.css';
import '../../css/p/p5qbymbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuhezrb5q"/><circle class="rjngqpptk"/><path class="p5qbymbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:service-plan" /></template>
