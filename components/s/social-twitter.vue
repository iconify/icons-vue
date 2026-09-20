<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm3h5jbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tm3h5jbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-twitter" /></template>
