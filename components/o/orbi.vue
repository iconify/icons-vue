<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abx_eo5fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abx_eo5fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:orbi" /></template>
