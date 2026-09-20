<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1_jmk1cr.css';
import '../../css/f/f3kmjcc1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="w1_jmk1cr"/><path class="f3kmjcc1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:toggle-on" /></template>
