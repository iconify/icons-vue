<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg9_g749x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg9_g749x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:summation-01" /></template>
