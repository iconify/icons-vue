<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izbfeq86f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izbfeq86f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-circle-filled" /></template>
