<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klfze56cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klfze56cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:table-view" /></template>
