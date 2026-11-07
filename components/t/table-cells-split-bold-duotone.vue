<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nayqy1c_r.css';
import '../../css/p/pfubdhgzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="pfubdhgzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-cells-split-bold-duotone" /></template>
