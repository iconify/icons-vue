<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6h73cb-x.css';
import '../../css/v/vpz4phbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6h73cb-x"/><path clip-rule="evenodd" class="vpz4phbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ssd-round-bold-duotone" /></template>
