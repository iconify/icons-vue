<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln9646oal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ln9646oal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pinterest-outline" /></template>
