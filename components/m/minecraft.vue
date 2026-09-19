<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp32vhbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sp32vhbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:minecraft" /></template>
