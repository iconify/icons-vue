<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6842ab4y.css';
import '../../css/m/mx48p9b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="r6842ab4y"/><path class="mx48p9b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-edit" /></template>
