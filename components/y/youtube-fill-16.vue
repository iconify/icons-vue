<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bna-rjbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bna-rjbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:youtube-fill-16" /></template>
