<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l51imkbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l51imkbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shovel" /></template>
