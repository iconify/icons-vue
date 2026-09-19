<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tegeywllk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tegeywllk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:push-button" /></template>
