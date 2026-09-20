<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0a42v_3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0a42v_3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:traffic-left-right" /></template>
