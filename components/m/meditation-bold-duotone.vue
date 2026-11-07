<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfx_j7n7f.css';
import '../../css/a/avzi4zbdf.css';
import '../../css/c/c8ow5lbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfx_j7n7f"/><path clip-rule="evenodd" class="avzi4zbdf"/><path class="c8ow5lbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:meditation-bold-duotone" /></template>
