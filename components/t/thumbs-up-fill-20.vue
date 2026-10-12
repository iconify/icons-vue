<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9g2lac9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c9g2lac9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:thumbs-up-fill-20" /></template>
