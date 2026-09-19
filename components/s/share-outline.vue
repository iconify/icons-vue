<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk_0u7b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk_0u7b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:share-outline" /></template>
