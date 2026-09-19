<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyh6tzb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uyh6tzb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:stackoverflow-wordmark" /></template>
