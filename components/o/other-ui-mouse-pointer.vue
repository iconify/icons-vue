<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw53exboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gw53exboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-mouse-pointer" /></template>
