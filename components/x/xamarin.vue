<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr_hp9bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jr_hp9bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:xamarin" /></template>
