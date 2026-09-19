<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj98vabvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oj98vabvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stethoscope" /></template>
