<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i--4ambuk.css';
import '../../css/q/qzo006suv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<circle class="i--4ambuk"/><path class="qzo006suv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sun-stroke-12" /></template>
