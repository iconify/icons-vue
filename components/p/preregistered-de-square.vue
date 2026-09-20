<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7gmyhb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x7gmyhb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-de-square" /></template>
