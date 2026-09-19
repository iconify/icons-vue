<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8aw4pb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b8aw4pb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-skip-forward-circle" /></template>
