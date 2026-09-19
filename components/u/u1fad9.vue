<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp51r9b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hp51r9b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:u1fad9" /></template>
