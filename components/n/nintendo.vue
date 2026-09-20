<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkjt7ccve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkjt7ccve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nintendo" /></template>
