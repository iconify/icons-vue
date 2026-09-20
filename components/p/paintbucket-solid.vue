<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr--kk2qu.css';
import '../../css/q/q4g6dlonh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rr--kk2qu"/><path class="q4g6dlonh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paintbucket-solid" /></template>
