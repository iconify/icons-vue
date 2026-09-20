<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2yb-98oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2yb-98oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:send" /></template>
