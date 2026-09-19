<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjxv9lbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qjxv9lbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:png-download" /></template>
