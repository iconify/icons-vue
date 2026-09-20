<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3jht202b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p3jht202b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-envelope-right-with-baht" /></template>
