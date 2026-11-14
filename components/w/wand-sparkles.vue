<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng2jmjb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng2jmjb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wand-sparkles" /></template>
