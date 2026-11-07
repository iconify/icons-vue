<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdob9slbu.css';
import '../../css/v/v3h9yd14e.css';
import '../../css/h/ht8rgl0oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdob9slbu"/><path class="v3h9yd14e"/><path class="ht8rgl0oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:to-pip-bold-duotone" /></template>
