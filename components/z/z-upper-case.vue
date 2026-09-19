<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo7efloty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":503,"height":735};
const content = `<path class="mo7efloty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:z-upper-case" /></template>
