<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as_3gib-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as_3gib-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:window" /></template>
