<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk5sbi9lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk5sbi9lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:user-rectangle" /></template>
