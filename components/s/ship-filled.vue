<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki9tfbbtw.css';
import '../../css/v/vfhe1wb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9tfbbtw"/><path class="vfhe1wb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ship-filled" /></template>
