<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0y3-5b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0y3-5b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:unlock" /></template>
