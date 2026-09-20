<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw_83wk5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw_83wk5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:restart-fill" /></template>
