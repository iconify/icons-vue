<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq3m62bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dq3m62bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:temple" /></template>
