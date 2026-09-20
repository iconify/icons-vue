<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtehi7nkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gtehi7nkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shield-1-remix" /></template>
