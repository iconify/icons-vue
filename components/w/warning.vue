<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajn19m5qg.css';
import '../../css/c/cadm6kfiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ajn19m5qg"/><path class="cadm6kfiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:warning" /></template>
