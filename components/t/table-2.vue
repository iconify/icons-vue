<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blgxw44em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blgxw44em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:table-2" /></template>
