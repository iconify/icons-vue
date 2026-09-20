<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhv7_-hzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhv7_-hzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-number-9-filled" /></template>
