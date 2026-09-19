<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0grz6btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="x0grz6btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:sina-weibo-small" /></template>
