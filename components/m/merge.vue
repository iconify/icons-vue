<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fochnqkrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fochnqkrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:merge" /></template>
