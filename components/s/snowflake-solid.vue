<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbne24udz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbne24udz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:snowflake-solid" /></template>
