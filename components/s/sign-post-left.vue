<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otumz-d4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="otumz-d4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sign-post-left" /></template>
