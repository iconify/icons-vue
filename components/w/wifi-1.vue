<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b179psbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b179psbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wifi-1" /></template>
