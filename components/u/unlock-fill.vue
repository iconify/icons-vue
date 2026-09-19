<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb4gcfb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nb4gcfb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:unlock-fill" /></template>
