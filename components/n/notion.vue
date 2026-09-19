<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4plou9lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4plou9lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notion" /></template>
