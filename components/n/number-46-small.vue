<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmxwfq3ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmxwfq3ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-46-small" /></template>
