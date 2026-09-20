<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu20q1vfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hu20q1vfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-behind-desk" /></template>
