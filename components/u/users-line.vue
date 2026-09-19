<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbykosn1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="rbykosn1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:users-line" /></template>
