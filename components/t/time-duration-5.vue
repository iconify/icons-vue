<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfn8rcgml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfn8rcgml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:time-duration-5" /></template>
