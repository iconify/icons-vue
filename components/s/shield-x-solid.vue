<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhumhpb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhumhpb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-x-solid" /></template>
