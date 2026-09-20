<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa1lvmb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fa1lvmb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-forward-circle-bold" /></template>
