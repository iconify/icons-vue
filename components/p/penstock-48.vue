<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoae257bl.css';
import '../../css/g/gi5oa8bic.css';
import '../../css/h/hcflecbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aoae257bl"/><path class="gi5oa8bic"/><path class="hcflecbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:penstock-48" /></template>
