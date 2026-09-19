<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amy0yq-al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="amy0yq-al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wechat-small" /></template>
