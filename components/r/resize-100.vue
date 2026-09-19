<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2-mbfr7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q2-mbfr7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:resize-100" /></template>
