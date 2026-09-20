<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_gx5lmul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_gx5lmul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rectangle-vertical-filled" /></template>
