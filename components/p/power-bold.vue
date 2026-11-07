<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvhv_7sne.css';
import '../../css/x/xrl_dh1so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvhv_7sne"/><path class="xrl_dh1so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:power-bold" /></template>
