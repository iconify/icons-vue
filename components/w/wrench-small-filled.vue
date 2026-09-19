<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu8s29bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qu8s29bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wrench-small-filled" /></template>
