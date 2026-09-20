<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve_zacdrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ve_zacdrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:triangle-11" /></template>
