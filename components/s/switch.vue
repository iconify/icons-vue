<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twxpq_bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="twxpq_bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:switch" /></template>
