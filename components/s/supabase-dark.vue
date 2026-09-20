<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd36bjb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dd36bjb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:supabase-dark" /></template>
