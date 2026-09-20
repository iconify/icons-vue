<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynaascbgh.css';
import '../../css/f/fephoqb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynaascbgh"/><path clip-rule="evenodd" class="fephoqb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:siderbar-outline" /></template>
