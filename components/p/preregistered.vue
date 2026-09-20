<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1wosjt8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1wosjt8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered" /></template>
