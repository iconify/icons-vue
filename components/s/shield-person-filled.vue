<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa3zcxb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa3zcxb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shield-person-filled" /></template>
