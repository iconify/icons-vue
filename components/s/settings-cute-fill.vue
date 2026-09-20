<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgj0ydbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zgj0ydbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:settings-cute-fill" /></template>
