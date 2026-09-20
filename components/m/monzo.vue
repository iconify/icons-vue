<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st3sq4bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st3sq4bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:monzo" /></template>
