<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy_gakbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy_gakbdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:xbox" /></template>
