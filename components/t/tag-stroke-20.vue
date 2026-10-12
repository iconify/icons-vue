<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxyh9s5lq.css';
import '../../css/f/f5hnvrbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kxyh9s5lq"/><path class="f5hnvrbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tag-stroke-20" /></template>
