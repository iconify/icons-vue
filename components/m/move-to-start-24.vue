<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3sutw5kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3sutw5kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:move-to-start-24" /></template>
