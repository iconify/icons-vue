<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk9vcn4yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk9vcn4yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-bolt" /></template>
