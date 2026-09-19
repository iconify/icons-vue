<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0y6dt08n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0y6dt08n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:monkey-filled" /></template>
