<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6ljd6b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j6ljd6b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-alt-slash-solid" /></template>
