<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8io8zx6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8io8zx6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:squares-exclude" /></template>
