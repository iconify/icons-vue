<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4s-3hy_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p4s-3hy_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wireless-charge" /></template>
