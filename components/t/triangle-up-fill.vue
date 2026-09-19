<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg52xz9ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qg52xz9ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:triangle-up-fill" /></template>
