<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5yxrcd3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l5yxrcd3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:unlink" /></template>
