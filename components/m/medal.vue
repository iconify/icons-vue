<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk1t6fbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lk1t6fbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:medal" /></template>
