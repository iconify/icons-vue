<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivy_7zb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ivy_7zb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:refresh-doing-outline" /></template>
