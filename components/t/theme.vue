<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytrbdtb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytrbdtb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:theme" /></template>
