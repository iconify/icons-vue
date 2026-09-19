<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os6dgybfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os6dgybfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:user-plus-solid" /></template>
