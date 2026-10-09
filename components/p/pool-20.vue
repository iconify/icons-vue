<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfl-1pr-y.css';
import '../../css/b/b8fd5ibpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lfl-1pr-y"/><path class="b8fd5ibpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pool-20" /></template>
