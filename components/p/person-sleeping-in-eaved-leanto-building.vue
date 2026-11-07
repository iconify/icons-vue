<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr5o4wufh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tr5o4wufh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sleeping-in-eaved-leanto-building" /></template>
