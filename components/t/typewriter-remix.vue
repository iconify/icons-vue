<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9finxy4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9finxy4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:typewriter-remix" /></template>
