<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trnm7w1kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="trnm7w1kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-inverted-large-outline" /></template>
