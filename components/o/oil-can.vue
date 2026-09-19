<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xce91zbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xce91zbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:oil-can" /></template>
