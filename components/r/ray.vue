<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psgtoi7vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psgtoi7vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ray" /></template>
