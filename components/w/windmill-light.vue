<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra4xehcyp.css';
import '../../css/z/zj7rmmb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ra4xehcyp"/><path class="zj7rmmb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:windmill-light" /></template>
