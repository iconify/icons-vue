<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os7puxbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b os7puxbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reading-glass" /></template>
