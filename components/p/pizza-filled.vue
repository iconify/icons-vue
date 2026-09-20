<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn_dg_3pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn_dg_3pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pizza-filled" /></template>
