<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yumz50bwm.css';
import '../../css/f/fu_1axbuk.css';
import '../../css/w/wd-cb2baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yumz50bwm"/><path class="fu_1axbuk"/><path class="wd-cb2baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waste-to-energy-20" /></template>
