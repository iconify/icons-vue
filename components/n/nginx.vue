<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iet1eb9kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iet1eb9kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nginx" /></template>
