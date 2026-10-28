<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8wq5kgjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wq5kgjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubuntu" /></template>
