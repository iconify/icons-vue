<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdc2ltdiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tdc2ltdiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-github" /></template>
