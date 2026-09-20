<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7hwuabpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a7hwuabpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-16-solid" /></template>
