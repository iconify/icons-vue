<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8goy0baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8goy0baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:point" /></template>
