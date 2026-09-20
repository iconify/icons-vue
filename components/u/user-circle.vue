<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnm3uwu-x.css';
import '../../css/w/wwvjbde6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gnm3uwu-x"/><path class="wwvjbde6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:user-circle" /></template>
