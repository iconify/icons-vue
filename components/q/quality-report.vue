<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-mv4pbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-mv4pbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:quality-report" /></template>
