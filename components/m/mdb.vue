<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4c4oxb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="r4c4oxb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:mdb" /></template>
