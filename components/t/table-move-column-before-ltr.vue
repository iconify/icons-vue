<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge46vpt7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ge46vpt7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:table-move-column-before-ltr" /></template>
