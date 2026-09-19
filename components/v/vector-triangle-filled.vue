<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx5apzz_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx5apzz_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vector-triangle-filled" /></template>
