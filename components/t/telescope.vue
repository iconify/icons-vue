<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtjq6nrol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gtjq6nrol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:telescope" /></template>
