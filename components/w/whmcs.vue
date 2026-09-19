<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1yghxbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a1yghxbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:whmcs" /></template>
