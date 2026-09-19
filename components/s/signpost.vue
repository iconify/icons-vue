<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm0y8yomm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hm0y8yomm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:signpost" /></template>
