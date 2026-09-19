<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oczhvxbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oczhvxbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:volvo" /></template>
