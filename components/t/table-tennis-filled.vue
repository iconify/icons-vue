<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6etw8bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6etw8bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-tennis-filled" /></template>
