<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw1_4lbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw1_4lbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paper-airplane-solid" /></template>
