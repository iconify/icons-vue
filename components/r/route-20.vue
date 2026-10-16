<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2ephobok.css';
import '../../css/c/clgy_7biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p2ephobok"/><path class="clgy_7biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:route-20" /></template>
