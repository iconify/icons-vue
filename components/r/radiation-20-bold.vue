<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_-yre08v.css';
import '../../css/z/z74qi6bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p_-yre08v"/><path class="z74qi6bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiation-20-bold" /></template>
