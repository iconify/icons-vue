<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dups90d2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dups90d2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:world-latitude" /></template>
