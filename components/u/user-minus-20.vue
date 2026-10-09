<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta36lgbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ta36lgbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-minus-20" /></template>
