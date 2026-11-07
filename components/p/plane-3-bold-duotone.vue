<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ruqrb_t.css';
import '../../css/i/iyp-m0sxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_ruqrb_t"/><path class="iyp-m0sxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plane-3-bold-duotone" /></template>
