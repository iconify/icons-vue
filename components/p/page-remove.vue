<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1xd35blt.css';
import '../../css/s/sou039b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="f1xd35blt"/><path class="sou039b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-remove" /></template>
