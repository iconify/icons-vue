<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2bkbc2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ud2bkbc2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pressure" /></template>
