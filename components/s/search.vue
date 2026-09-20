<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n82zcy6-h.css';
import '../../css/c/clhe_ezsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n82zcy6-h"/><path class="clhe_ezsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:search" /></template>
