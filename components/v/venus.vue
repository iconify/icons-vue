<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1byepbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="s1byepbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:venus" /></template>
