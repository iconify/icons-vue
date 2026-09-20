<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-dt9b8vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-dt9b8vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sad-square-bold" /></template>
