<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukw6yum5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="ukw6yum5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:transgender-alt" /></template>
