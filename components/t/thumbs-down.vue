<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6nmeno7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h6nmeno7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:thumbs-down" /></template>
