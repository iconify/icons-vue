<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o991c4n6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o991c4n6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:yugabytedb-wordmark" /></template>
