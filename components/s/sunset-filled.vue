<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smvh-7b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smvh-7b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sunset-filled" /></template>
