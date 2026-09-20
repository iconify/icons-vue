<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzb5yt4nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vzb5yt4nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tag-solid" /></template>
