<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1u1sjbgx.css';
import '../../css/s/sqkdmebni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1u1sjbgx"/><path clip-rule="evenodd" class="sqkdmebni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ssd-square-bold-duotone" /></template>
