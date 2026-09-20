<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0-jzjbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g0-jzjbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:quaker-star-on-square" /></template>
