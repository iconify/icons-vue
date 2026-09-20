<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n91xzbc8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n91xzbc8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-steam" /></template>
