<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgt-dnbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fgt-dnbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pscircle" /></template>
