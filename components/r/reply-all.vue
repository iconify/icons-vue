<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay1xdy5oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1600};
const content = `<path class="ay1xdy5oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:reply-all" /></template>
