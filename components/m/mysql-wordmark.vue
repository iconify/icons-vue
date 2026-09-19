<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlnshvmru.css';
import '../../css/p/paw_-0u1j.css';
import '../../css/u/uc8gne65u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tlnshvmru"/><path class="paw_-0u1j"/><path class="uc8gne65u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mysql-wordmark" /></template>
