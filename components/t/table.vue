<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9-e4db2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9-e4db2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:table" /></template>
