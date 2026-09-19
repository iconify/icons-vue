<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj0h9ub6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj0h9ub6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-check-filled" /></template>
