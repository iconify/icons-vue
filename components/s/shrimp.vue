<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be0ngpbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="be0ngpbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shrimp" /></template>
