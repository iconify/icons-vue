<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocvqb6bxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocvqb6bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zzz-solid" /></template>
