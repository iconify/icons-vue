<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a41ck6p4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a41ck6p4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:seedling-filled" /></template>
