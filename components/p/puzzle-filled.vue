<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2h02n6ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2h02n6ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:puzzle-filled" /></template>
