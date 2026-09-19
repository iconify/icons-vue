<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrb5xpbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="zrb5xpbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:youtube" /></template>
