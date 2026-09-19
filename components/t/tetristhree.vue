<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oag9yzbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1024};
const content = `<path class="oag9yzbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tetristhree" /></template>
