<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a98i3bc2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="a98i3bc2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:test-tubes" /></template>
