<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juz-jcb_p.css';
import '../../css/v/vbotk2bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="juz-jcb_p"/><path class="vbotk2bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:noise-reduction-20" /></template>
