<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn20dkynd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="qn20dkynd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:nail" /></template>
