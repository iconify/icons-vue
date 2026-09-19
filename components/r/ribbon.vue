<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaxfskgkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":420,"height":850};
const content = `<path class="kaxfskgkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:ribbon" /></template>
