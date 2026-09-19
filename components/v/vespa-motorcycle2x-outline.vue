<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2r2-mbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d2r2-mbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vespa-motorcycle2x-outline" /></template>
