<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re-9-t6rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="re-9-t6rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:meilisearch-light" /></template>
