<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xijfztbzl.css';
import '../../css/f/fu-ei7b7x.css';
import '../../css/o/ohcq6p68c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xijfztbzl"/><path class="fu-ei7b7x"/><path class="ohcq6p68c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:person-walking-48-bold" /></template>
