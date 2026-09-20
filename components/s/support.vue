<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi2bydbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bi2bydbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:support" /></template>
