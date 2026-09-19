<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2cc8ebfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="u2cc8ebfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelpotionalt" /></template>
