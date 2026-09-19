<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsmsgs7un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dsmsgs7un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mnx" /></template>
