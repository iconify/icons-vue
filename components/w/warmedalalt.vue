<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2mfbmb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="v2mfbmb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:warmedalalt" /></template>
