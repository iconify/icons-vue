<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otd35ob1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2200,"height":2200};
const content = `<path class="otd35ob1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:swr-light" /></template>
