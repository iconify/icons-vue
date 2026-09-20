<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9deqsbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9deqsbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:railway" /></template>
