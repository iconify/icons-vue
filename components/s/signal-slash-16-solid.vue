<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bipozlu_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bipozlu_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:signal-slash-16-solid" /></template>
