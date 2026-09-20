<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w10uxx11n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="w10uxx11n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:restaurant-11" /></template>
