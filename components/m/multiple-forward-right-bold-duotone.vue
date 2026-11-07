<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytjd3_bxd.css';
import '../../css/r/rj2mhcbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytjd3_bxd"/><path clip-rule="evenodd" class="rj2mhcbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:multiple-forward-right-bold-duotone" /></template>
