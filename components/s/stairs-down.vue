<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3j6f0b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3j6f0b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stairs-down" /></template>
