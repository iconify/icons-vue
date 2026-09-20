<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7jl220f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7jl220f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:omadacloud" /></template>
