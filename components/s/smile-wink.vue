<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we4ibnb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we4ibnb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:smile-wink" /></template>
