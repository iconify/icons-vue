<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rahtcccgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="rahtcccgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-skype" /></template>
