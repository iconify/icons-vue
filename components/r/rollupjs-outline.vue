<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt6rq6zsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mt6rq6zsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rollupjs-outline" /></template>
