<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukooq9bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ukooq9bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:waning-crescent-moon-symbol" /></template>
