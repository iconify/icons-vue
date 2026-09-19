<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzyd7bckj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bzyd7bckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:wrench" /></template>
