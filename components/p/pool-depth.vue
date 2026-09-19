<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-mx6rb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-mx6rb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pool-depth" /></template>
