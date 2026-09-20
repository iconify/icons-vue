<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao2q88qfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao2q88qfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-star" /></template>
