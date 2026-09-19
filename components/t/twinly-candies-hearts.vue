<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loibq93je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loibq93je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinly-candies-hearts" /></template>
