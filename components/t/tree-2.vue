<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeat3sbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="eeat3sbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:tree-2" /></template>
