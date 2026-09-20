<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzksm6bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qzksm6bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-dropbox" /></template>
