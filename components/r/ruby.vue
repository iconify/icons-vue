<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz2t2e3bo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lz2t2e3bo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ruby" /></template>
