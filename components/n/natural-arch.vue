<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aslg49b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aslg49b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:natural-arch" /></template>
