<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhqk2bbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="jhqk2bbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mill-sign" /></template>
