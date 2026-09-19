<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq-n_37ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sq-n_37ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:text-underline" /></template>
