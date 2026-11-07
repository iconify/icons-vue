<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4s4u8b9z.css';
import '../../css/o/ortpaq31n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4s4u8b9z"/><path class="ortpaq31n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-cross-bold-duotone" /></template>
