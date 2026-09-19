<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_szxhbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="m_szxhbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:onenote" /></template>
