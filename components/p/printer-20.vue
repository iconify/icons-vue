<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9m217b_a.css';
import '../../css/a/azvvpmbsy.css';
import '../../css/h/hk39bac5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r9m217b_a"/><path class="azvvpmbsy"/><path class="hk39bac5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:printer-20" /></template>
