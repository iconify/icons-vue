<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-yb0tb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k-yb0tb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:mariadb-wordmark" /></template>
