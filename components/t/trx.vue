<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfcyrccjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bfcyrccjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:trx" /></template>
