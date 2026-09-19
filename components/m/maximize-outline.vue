<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doex5ofaj.css';
import '../../css/u/u9i5pqlkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doex5ofaj"/><path class="u9i5pqlkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:maximize-outline" /></template>
