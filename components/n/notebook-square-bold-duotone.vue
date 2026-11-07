<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6yy04fix.css';
import '../../css/o/o4u834bpr.css';
import '../../css/a/avmk686_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6yy04fix"/><path class="o4u834bpr"/><path class="avmk686_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notebook-square-bold-duotone" /></template>
