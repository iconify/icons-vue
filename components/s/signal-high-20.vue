<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paev8qj-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="paev8qj-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-high-20" /></template>
