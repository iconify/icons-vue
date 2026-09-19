<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vet3pibcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vet3pibcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:stopwatch" /></template>
