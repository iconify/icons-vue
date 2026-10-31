<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp46v6-0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xp46v6-0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-book-in-eaved-gabled-building-with-chimney" /></template>
