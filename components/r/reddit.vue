<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zodqo1c7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zodqo1c7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:reddit" /></template>
