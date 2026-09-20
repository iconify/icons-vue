<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0xxt-34c.css';
import '../../css/f/f2cq9cczx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0xxt-34c"/><path class="f2cq9cczx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mask-happly-bold-duotone" /></template>
