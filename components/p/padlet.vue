<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzx64zf2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jzx64zf2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:padlet" /></template>
