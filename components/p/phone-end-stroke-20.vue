<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b21qzcbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b21qzcbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-end-stroke-20" /></template>
