<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cegqsyl-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cegqsyl-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-moon-20" /></template>
