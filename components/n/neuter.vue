<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1_805bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b1_805bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:neuter" /></template>
