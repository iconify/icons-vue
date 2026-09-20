<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcea5wauz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcea5wauz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:spreaker" /></template>
