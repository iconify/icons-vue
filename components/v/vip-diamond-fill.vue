<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e27oc0i3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e27oc0i3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vip-diamond-fill" /></template>
