<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwr6088ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hwr6088ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:money-bill-1" /></template>
