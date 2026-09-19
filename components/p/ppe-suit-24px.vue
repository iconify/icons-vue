<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbrug46qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbrug46qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-suit-24px" /></template>
