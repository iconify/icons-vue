<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gydzj4ccz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gydzj4ccz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:syrup-jug" /></template>
