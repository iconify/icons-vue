<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz1whib-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz1whib-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:social-distancing-correct-2" /></template>
