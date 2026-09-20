<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lca8tgbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lca8tgbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:minus-solid" /></template>
