<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysk3uyb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ysk3uyb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:oral-contraception-pillsx21" /></template>
