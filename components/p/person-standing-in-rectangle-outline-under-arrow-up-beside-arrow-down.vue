<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qazvk2b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qazvk2b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-in-rectangle-outline-under-arrow-up-beside-arrow-down" /></template>
