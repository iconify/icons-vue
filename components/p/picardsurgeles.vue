<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cli45hbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cli45hbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:picardsurgeles" /></template>
