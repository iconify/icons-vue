<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd9lj4vea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rd9lj4vea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:users" /></template>
