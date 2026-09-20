<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg34m8bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sg34m8bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-behance" /></template>
