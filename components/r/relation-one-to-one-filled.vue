<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ara_c1bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ara_c1bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:relation-one-to-one-filled" /></template>
