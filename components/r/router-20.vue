<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx2n-7xqn.css';
import '../../css/b/bpbl5vkki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zx2n-7xqn"/><path class="bpbl5vkki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:router-20" /></template>
