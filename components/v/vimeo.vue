<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd1syvbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sd1syvbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:vimeo" /></template>
