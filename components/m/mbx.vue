<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl8d4jd3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl8d4jd3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mbx" /></template>
