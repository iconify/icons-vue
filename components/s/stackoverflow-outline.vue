<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh6ky0bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lh6ky0bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stackoverflow-outline" /></template>
