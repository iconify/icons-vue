<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_7jlsb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i_7jlsb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:megaphone" /></template>
