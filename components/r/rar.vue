<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4gvovshw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="r4gvovshw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:rar" /></template>
