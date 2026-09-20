<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blwu7db1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blwu7db1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:seo" /></template>
