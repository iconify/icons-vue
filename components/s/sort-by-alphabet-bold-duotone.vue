<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmm_ovqpx.css';
import '../../css/b/bem6xnbwz.css';
import '../../css/y/yx9j9-c-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmm_ovqpx"/><path clip-rule="evenodd" class="bem6xnbwz"/><path class="yx9j9-c-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sort-by-alphabet-bold-duotone" /></template>
