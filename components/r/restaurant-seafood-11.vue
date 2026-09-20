<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buto0mbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="buto0mbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:restaurant-seafood-11" /></template>
