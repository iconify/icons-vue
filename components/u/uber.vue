<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9er9icpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="k9er9icpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:uber" /></template>
