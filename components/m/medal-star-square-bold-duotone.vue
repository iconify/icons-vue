<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv2msx5_t.css';
import '../../css/v/v5fufdeal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2msx5_t"/><path clip-rule="evenodd" class="v5fufdeal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-square-bold-duotone" /></template>
