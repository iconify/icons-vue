<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oakvv7b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oakvv7b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-facebook" /></template>
