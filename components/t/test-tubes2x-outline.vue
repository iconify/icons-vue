<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whemcl2nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="whemcl2nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:test-tubes2x-outline" /></template>
