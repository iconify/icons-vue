<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s51np_b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s51np_b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:quran-01" /></template>
