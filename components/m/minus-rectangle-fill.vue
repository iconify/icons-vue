<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4el9hdzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="p4el9hdzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:minus-rectangle-fill" /></template>
