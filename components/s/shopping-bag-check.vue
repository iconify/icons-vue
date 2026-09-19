<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvh-a_b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvh-a_b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-bag-check" /></template>
