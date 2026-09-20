<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_sjb1a9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_sjb1a9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shirt" /></template>
