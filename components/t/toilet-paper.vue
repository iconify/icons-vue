<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipn5owbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ipn5owbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:toilet-paper" /></template>
