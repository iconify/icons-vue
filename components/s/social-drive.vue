<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krcsaxb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="krcsaxb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-drive" /></template>
