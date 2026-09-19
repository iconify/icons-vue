<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyr-9pbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fyr-9pbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:trojan" /></template>
