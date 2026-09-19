<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9bknptjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9bknptjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-solid" /></template>
