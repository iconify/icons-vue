<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/berfx5bid.css';
import '../../css/x/xvhi1u9pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="berfx5bid"/><path class="xvhi1u9pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:python" /></template>
