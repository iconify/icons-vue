<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dunl5u65t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="dunl5u65t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:telegram" /></template>
