<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyljurtoy.css';
import '../../css/b/bqclo9bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyljurtoy"/><path class="bqclo9bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:siren-off-filled" /></template>
