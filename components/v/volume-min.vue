<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmyxs9_0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmyxs9_0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:volume-min" /></template>
