<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vichwvp_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vichwvp_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rectangle" /></template>
