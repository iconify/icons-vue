<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efdqis5-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efdqis5-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:university-outline" /></template>
