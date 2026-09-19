<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j779vsc8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j779vsc8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sink" /></template>
