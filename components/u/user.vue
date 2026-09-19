<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5rwa8b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="z5rwa8b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:user" /></template>
