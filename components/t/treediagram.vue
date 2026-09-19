<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj-au7bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="wj-au7bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:treediagram" /></template>
