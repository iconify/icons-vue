<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r53vu5kmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r53vu5kmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunrise-fill" /></template>
