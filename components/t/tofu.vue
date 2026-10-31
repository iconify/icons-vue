<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0b1pobvd.css';
import '../../css/n/nxk669c7l.css';
import '../../css/g/g147opbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="b0b1pobvd"/><path class="nxk669c7l"/><path class="g147opbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:tofu" /></template>
