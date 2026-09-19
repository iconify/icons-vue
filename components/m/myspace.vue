<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kywqgvmdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kywqgvmdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:myspace" /></template>
