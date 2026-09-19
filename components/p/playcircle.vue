<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iel2hrbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iel2hrbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:playcircle" /></template>
