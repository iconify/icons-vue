<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqwuxfb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hqwuxfb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:settings-fill-26" /></template>
