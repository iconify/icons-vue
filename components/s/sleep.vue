<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-kj6cbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-kj6cbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:sleep" /></template>
