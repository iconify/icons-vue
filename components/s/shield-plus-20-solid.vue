<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezbwsos2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ezbwsos2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-plus-20-solid" /></template>
