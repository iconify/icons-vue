<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf4iecijn.css';
import '../../css/y/ylwrz8bdu.css';
import '../../css/a/a9vul7b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pf4iecijn"/><path class="ylwrz8bdu"/><path class="a9vul7b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stadium-48-bold" /></template>
