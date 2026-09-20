<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agm3vdb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agm3vdb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:signature" /></template>
