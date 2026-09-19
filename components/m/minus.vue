<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn8u5lb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn8u5lb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:minus" /></template>
