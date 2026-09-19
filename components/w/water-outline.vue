<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h36wngbkh.css';
import '../../css/b/b29c1cwoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h36wngbkh"/><path class="b29c1cwoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:water-outline" /></template>
