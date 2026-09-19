<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyolq2bek.css';
import '../../css/j/jo-7oophi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="vyolq2bek"/><path class="jo-7oophi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reader-outline" /></template>
