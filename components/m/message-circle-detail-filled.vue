<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcgedqb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcgedqb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-detail-filled" /></template>
