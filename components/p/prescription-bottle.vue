<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb3bc7b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb3bc7b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:prescription-bottle" /></template>
