<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5-k6bcwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a5-k6bcwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:typescript-outline" /></template>
