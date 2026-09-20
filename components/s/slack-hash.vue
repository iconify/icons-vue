<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-0k38b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x-0k38b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:slack-hash" /></template>
