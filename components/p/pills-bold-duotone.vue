<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9h5fmbqx.css';
import '../../css/h/hsjczmubo.css';
import '../../css/x/x5yc8ybio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9h5fmbqx"/><path class="hsjczmubo"/><path class="x5yc8ybio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-bold-duotone" /></template>
