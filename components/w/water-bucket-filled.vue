<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt6gpltkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xt6gpltkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:water-bucket-filled" /></template>
