<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enn3tn4xs.css';
import '../../css/w/w-oye57eg.css';
import '../../css/k/k3301qb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enn3tn4xs"/><path class="w-oye57eg"/><path class="k3301qb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-new-square-bold" /></template>
