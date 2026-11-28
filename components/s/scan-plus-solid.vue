<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkxesj40f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkxesj40f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scan-plus-solid" /></template>
