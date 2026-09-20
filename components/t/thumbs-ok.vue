<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3o_rcben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3o_rcben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:thumbs-ok" /></template>
