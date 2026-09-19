<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_3oub9zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_3oub9zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:personal-hygiene-hand-sanitizer-spray-virus-block" /></template>
